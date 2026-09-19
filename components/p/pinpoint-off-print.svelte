<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/uzrocibyu.css';
import '../../css/f/fthxges_p.css';
import '../../css/c/c6am73bhf.css';
import '../../css/g/g42dkccnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="uzrocibyu"/><path class="fthxges_p"/><path clip-rule="evenodd" class="c6am73bhf"/><path clip-rule="evenodd" class="g42dkccnc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:pinpoint-off-print" {...props}></Icon>
