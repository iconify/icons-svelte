<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8xmm274s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q8xmm274s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-question-help-circle-2" {...props}></Icon>
