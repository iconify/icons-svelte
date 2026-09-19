<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ruk79mbge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ruk79mbge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:lane-insert-below" {...props}></Icon>
