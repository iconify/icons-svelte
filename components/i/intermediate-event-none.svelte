<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gab9z0b4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="gab9z0b4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:intermediate-event-none" {...props}></Icon>
