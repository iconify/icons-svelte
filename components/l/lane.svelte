<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdg0_mb9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="jdg0_mb9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:lane" {...props}></Icon>
