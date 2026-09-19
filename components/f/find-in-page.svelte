<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/noad8bc2x.css';
import '../../css/v/vbgzj3b-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="noad8bc2x"/><path class="vbgzj3b-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:find-in-page" {...props}></Icon>
