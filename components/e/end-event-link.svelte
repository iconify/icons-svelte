<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipyo4j7ey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ipyo4j7ey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:end-event-link" {...props}></Icon>
