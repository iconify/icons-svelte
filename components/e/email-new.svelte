<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xb_pvbb1s.css';
import '../../css/s/sku11tm4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xb_pvbb1s"/><circle class="sku11tm4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:email-new" {...props}></Icon>
