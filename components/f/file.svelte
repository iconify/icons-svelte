<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-qykno5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="i-qykno5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:file" {...props}></Icon>
