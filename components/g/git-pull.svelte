<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/es2q0bbgb.css';
import '../../css/c/cxua9cc6r.css';
import '../../css/t/tdtk3xqjc.css';
import '../../css/m/mo5qvibyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="es2q0bbgb"/><path class="cxua9cc6r"/><path class="tdtk3xqjc"/><path class="mo5qvibyu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:git-pull" {...props}></Icon>
