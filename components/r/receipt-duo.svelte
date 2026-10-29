<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/kbz71jyrz.css';
import '../../css/p/perttu9bq.css';
import '../../css/r/ri2oegbdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="kbz71jyrz"/><path class="perttu9bq wm-a"/><path class="ri2oegbdi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:receipt-duo" {...props}></Icon>
