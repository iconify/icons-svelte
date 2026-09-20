<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/a/ap26nqnxv.css';
import '../../css/l/lsz6fibgl.css';
import '../../css/a/acqdoh0bi.css';
import '../../css/v/vln_qclhe.css';
import '../../css/z/zbkvzbrvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ap26nqnxv"/><path class="lsz6fibgl"/><path class="acqdoh0bi"/><path class="vln_qclhe"/><path class="zbkvzbrvx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:android-logo" {...props}></Icon>
