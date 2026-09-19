<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4o_uwagr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="i4o_uwagr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:intermediate-event-catch-non-interrupting-multiple" {...props}></Icon>
