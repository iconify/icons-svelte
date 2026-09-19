<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgblcmbsv.css';
import '../../css/p/p_8a0397c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vgblcmbsv"/><path class="p_8a0397c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:lips" {...props}></Icon>
