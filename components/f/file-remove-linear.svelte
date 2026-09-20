<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/m0sfo-x4j.css';
import '../../css/e/e0cmz0boh.css';
import '../../css/z/zr35ecbmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="m0sfo-x4j"/><path class="e0cmz0boh"/><path class="zr35ecbmr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-remove-linear" {...props}></Icon>
