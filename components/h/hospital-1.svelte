<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/d2f8b2rvm.css';
import '../../css/k/k_wh-tamw.css';
import '../../css/q/qu42ndbsv.css';
import '../../css/q/qcj86obbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="d2f8b2rvm"/><path class="k_wh-tamw"/><path class="qu42ndbsv"/><path class="qcj86obbh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:hospital-1" {...props}></Icon>
