<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w182swarl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="w182swarl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:end-event-escalation" {...props}></Icon>
