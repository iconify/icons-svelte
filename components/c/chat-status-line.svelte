<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/w/wa5y1pppq.css';
import '../../css/p/pv46_kizc.css';
import '../../css/j/jxl67pbry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wa5y1pppq"/><path class="pv46_kizc"/><circle class="jxl67pbry"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:chat-status-line" {...props}></Icon>
