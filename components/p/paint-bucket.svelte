<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2ow9_bsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x2ow9_bsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:paint-bucket" {...props}></Icon>
