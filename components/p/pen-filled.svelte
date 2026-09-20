<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kem-rcb_x.css';
import '../../css/d/d2kvgvbvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<defs><path id="SVG9pcnZPUV" class="kem-rcb_x"/></defs><use href="#SVG9pcnZPUV" transform="translate(42.667 53.333)" class="d2kvgvbvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:pen-filled" {...props}></Icon>
