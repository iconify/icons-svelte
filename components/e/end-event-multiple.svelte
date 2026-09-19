<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2ca4z9jp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="p2ca4z9jp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:end-event-multiple" {...props}></Icon>
