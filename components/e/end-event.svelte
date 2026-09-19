<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2ds15qxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="h2ds15qxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:end-event" {...props}></Icon>
