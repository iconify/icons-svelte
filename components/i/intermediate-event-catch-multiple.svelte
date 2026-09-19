<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn1g7acrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="hn1g7acrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:intermediate-event-catch-multiple" {...props}></Icon>
