<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0cpixglr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="c0cpixglr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:hospital-jp-11" {...props}></Icon>
