<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ey1cel3wh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ey1cel3wh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:intermediate-event-throw-multiple" {...props}></Icon>
