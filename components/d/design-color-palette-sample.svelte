<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zl8i0-bnz.css';
import '../../css/c/cnn8c6pbg.css';
import '../../css/d/donjoukqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zl8i0-bnz"/><path class="cnn8c6pbg"/><path class="donjoukqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:design-color-palette-sample" {...props}></Icon>
