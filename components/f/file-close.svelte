<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/o/on3qdybdj.css';
import '../../css/d/dcnuadlyf.css';
import '../../css/y/ygbp9l3zb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="on3qdybdj"/><path class="dcnuadlyf"/><path class="ygbp9l3zb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:file-close" {...props}></Icon>
