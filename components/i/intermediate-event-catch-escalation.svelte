<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfamm_bvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="vfamm_bvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:intermediate-event-catch-escalation" {...props}></Icon>
