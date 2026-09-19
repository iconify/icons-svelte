<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hz94w__1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="hz94w__1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:event-subprocess-expanded" {...props}></Icon>
