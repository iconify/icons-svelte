<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flwdm6b3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="flwdm6b3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:intermediate-event-catch-message" {...props}></Icon>
