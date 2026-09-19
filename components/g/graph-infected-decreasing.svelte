<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/g/gph_qxhqv.css';
import '../../css/n/nsk92acve.css';
import '../../css/x/x2x40i-at.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gph_qxhqv"/><path class="nsk92acve"/><path class="x2x40i-at"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:graph-infected-decreasing" {...props}></Icon>
