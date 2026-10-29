<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/v/vzkm232hd.css';
import '../../css/s/s9ip9ibiv.css';
import '../../css/g/g25ktr9iv.css';
import '../../css/t/tkxcykbul.css';
import '../../css/r/rvvxdgw4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="vzkm232hd wm-deco"/><path class="s9ip9ibiv wm-deco"/><path class="g25ktr9iv wm-deco"/><path class="tkxcykbul wm-k"/><path class="rvvxdgw4h wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:face-mask-blueprint" {...props}></Icon>
