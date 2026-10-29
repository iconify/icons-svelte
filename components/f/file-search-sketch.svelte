<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/c085-k6yx.css';
import '../../css/b/bnocajebg.css';
import '../../css/u/u4cstkbgk.css';
import '../../css/o/oy1u0bcyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="c085-k6yx"/><path class="bnocajebg wm-a"/><path class="u4cstkbgk wm-k"/><path class="oy1u0bcyu wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-search-sketch" {...props}></Icon>
