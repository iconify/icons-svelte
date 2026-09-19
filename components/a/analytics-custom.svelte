<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dovqwxbmr.css';
import '../../css/m/mvazklbtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dovqwxbmr"/><path class="mvazklbtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:analytics-custom" {...props}></Icon>
