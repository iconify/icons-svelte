<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h855_yb2w.css';
import '../../css/v/vlrrqacry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="h855_yb2w"/><path class="vlrrqacry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:conditional-flow" {...props}></Icon>
