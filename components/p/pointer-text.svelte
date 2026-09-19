<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axs82db6h.css';
import '../../css/d/d1z03cbds.css';
import '../../css/t/tjlr-ybbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="axs82db6h"/><path class="d1z03cbds"/><path class="tjlr-ybbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:pointer-text" {...props}></Icon>
