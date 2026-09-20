<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pa3c4bb_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pa3c4bb_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:newline-rtl" {...props}></Icon>
