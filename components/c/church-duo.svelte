<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/n6banyksa.css';
import '../../css/r/rj2e_2hxk.css';
import '../../css/z/zrm_tfaxl.css';
import '../../css/y/y_fqobb9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="n6banyksa"/><path class="rj2e_2hxk wm-s"/><path class="zrm_tfaxl"/><path class="wm-a y_fqobb9e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:church-duo" {...props}></Icon>
