<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aawtl-1-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="aawtl-1-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:group" {...props}></Icon>
