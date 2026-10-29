<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/x/x4522uhjs.css';
import '../../css/n/nk-54lbig.css';
import '../../css/w/wrkbx9bny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="x4522uhjs"/><path class="nk-54lbig"/><path class="wm-a wrkbx9bny"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:dna" {...props}></Icon>
