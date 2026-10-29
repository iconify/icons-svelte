<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/kbz71jyrz.css';
import '../../css/w/w302-hd8l.css';
import '../../css/r/ri2oegbdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="kbz71jyrz"/><path class="w302-hd8l wm-a"/><path class="ri2oegbdi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:receipt-text-duo" {...props}></Icon>
