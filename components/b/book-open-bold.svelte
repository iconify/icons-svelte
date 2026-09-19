<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/s39efpwen.css';
import '../../css/u/ucu_1lbpn.css';
import '../../css/h/hscz_labj.css';
import '../../css/v/vbo612euk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="s39efpwen"/><path class="ucu_1lbpn"/><path clip-rule="evenodd" class="hscz_labj"/><path class="vbo612euk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:book-open-bold" {...props}></Icon>
