<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cq_yc_azc.css';
import '../../css/r/rq0x_wbbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cq_yc_azc"/><path class="rq0x_wbbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:metronome-filled" {...props}></Icon>
