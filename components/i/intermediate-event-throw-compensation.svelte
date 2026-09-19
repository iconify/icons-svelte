<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu4v0ccni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="vu4v0ccni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:intermediate-event-throw-compensation" {...props}></Icon>
