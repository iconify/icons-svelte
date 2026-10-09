<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_f719b8y.css';
import '../../css/z/zn32v344k.css';
import '../../css/d/d6cvwtbsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l_f719b8y"/><path class="zn32v344k"/><path class="d6cvwtbsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:beach-48-bold" {...props}></Icon>
