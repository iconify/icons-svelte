<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/vbe8lbbcp.css';
import '../../css/t/t3i5tcbhl.css';
import '../../css/e/ekp9r-bkm.css';
import '../../css/u/u8lek1bgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="vbe8lbbcp"/><path class="t3i5tcbhl"/><path class="ekp9r-bkm"/><path class="u8lek1bgr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:play-bug" {...props}></Icon>
