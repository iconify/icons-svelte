<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdl8c9zis.css';
import '../../css/y/ydhwbwb1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qdl8c9zis"/><path class="ydhwbwb1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:close-outline" {...props}></Icon>
