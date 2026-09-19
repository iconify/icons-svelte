<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4myg7bgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="x4myg7bgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:end-event-cancel" {...props}></Icon>
