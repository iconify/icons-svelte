<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnafimb2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="xnafimb2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:music-11" {...props}></Icon>
