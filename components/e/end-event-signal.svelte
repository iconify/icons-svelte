<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycchd8gvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ycchd8gvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:end-event-signal" {...props}></Icon>
