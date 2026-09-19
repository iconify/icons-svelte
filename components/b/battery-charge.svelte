<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dp1i03b6i.css';
import '../../css/q/qwoi0oksk.css';
import '../../css/c/cdwrhdcqt.css';
import '../../css/z/z9thu7bwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="dp1i03b6i"/><path class="qwoi0oksk"/><path class="cdwrhdcqt"/><path class="z9thu7bwc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:battery-charge" {...props}></Icon>
