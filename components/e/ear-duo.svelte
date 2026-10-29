<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/oh2cc2bmm.css';
import '../../css/t/tbbshccdj.css';
import '../../css/p/p4b-8obnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="oh2cc2bmm"/><path class="tbbshccdj wm-a"/><path class="p4b-8obnr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:ear-duo" {...props}></Icon>
