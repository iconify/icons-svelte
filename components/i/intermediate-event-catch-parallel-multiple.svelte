<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjjz6w-nb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="gjjz6w-nb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:intermediate-event-catch-parallel-multiple" {...props}></Icon>
