<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zt8_cobrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zt8_cobrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:face-activated-filled" {...props}></Icon>
