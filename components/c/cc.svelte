<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/timynoxoa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":1536};
const content = `<path class="timynoxoa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:cc" {...props}></Icon>
