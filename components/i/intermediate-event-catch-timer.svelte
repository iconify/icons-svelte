<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/euc22-b7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="euc22-b7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:intermediate-event-catch-timer" {...props}></Icon>
