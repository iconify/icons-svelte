<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsmongb3e.css';
import '../../css/r/r_bfxptlm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jsmongb3e"/><path class="r_bfxptlm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:link-external-ltr" {...props}></Icon>
