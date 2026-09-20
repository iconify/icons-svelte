<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/b/b78hd_rlk.css';
import '../../css/r/rn9fw-2lr.css';
import '../../css/y/yc2_9cb1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="b78hd_rlk"/><path class="rn9fw-2lr"/><path class="yc2_9cb1j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:phone-off" {...props}></Icon>
