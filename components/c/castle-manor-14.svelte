<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zt-67stkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="zt-67stkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:castle-manor-14" {...props}></Icon>
