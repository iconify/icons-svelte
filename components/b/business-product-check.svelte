<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxtl_ubyj.css';
import '../../css/s/s7-mspfvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yxtl_ubyj"/><path class="s7-mspfvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:business-product-check" {...props}></Icon>
