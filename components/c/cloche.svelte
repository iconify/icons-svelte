<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/p/p4pec6bad.css';
import '../../css/l/lvb-1jbul.css';
import '../../css/r/rv8wi5b_h.css';
import '../../css/r/rv-e2kbhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="p4pec6bad"/><path class="lvb-1jbul"/><path class="rv8wi5b_h"/><path class="rv-e2kbhh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:cloche" {...props}></Icon>
