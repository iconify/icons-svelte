<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/c/c1-gge6vc.css';
import '../../css/h/h0_d3oolp.css';
import '../../css/w/wxwl6_qzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="c1-gge6vc"/><path class="h0_d3oolp wm-a"/><path class="wxwl6_qzl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:message-circle-more-duo" {...props}></Icon>
