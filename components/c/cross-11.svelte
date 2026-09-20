<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/roudr1b6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="roudr1b6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:cross-11" {...props}></Icon>
