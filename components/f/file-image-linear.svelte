<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/z/zr35ecbmr.css';
import '../../css/b/b4cd0mb_l.css';
import '../../css/e/e0cmz0boh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="zr35ecbmr"/><path class="b4cd0mb_l"/><path class="e0cmz0boh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-image-linear" {...props}></Icon>
