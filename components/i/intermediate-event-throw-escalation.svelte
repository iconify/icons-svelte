<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbjxngb3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="dbjxngb3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:intermediate-event-throw-escalation" {...props}></Icon>
