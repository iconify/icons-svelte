<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5ws23v3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="w5ws23v3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:process-meta-task" {...props}></Icon>
