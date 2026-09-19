<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zeujr8b0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="zeujr8b0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:intermediate-event-throw-signal" {...props}></Icon>
