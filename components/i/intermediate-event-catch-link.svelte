<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hu1h2lvpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="hu1h2lvpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:intermediate-event-catch-link" {...props}></Icon>
