<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldzc12j9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ldzc12j9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:end-event-error" {...props}></Icon>
