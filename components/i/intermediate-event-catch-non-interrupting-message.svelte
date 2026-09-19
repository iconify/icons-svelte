<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jv6qv8ips.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="jv6qv8ips"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:intermediate-event-catch-non-interrupting-message" {...props}></Icon>
