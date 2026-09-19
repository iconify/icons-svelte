<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/c_kplcszs.css';
import '../../css/v/vfymv3unk.css';
import '../../css/q/qsz9j-v2y.css';
import '../../css/t/td1hxgbap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="c_kplcszs"/><path class="vfymv3unk"/><path class="qsz9j-v2y"/><path class="td1hxgbap"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:monster" {...props}></Icon>
