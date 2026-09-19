<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg_ct5bjf.css';
import '../../css/e/es579g_1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vg_ct5bjf"/><path class="es579g_1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:navaid-vhfor" {...props}></Icon>
