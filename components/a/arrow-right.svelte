<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxlvxlbey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qxlvxlbey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:arrow-right" {...props}></Icon>
