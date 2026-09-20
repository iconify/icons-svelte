<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlg8d3b5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="dlg8d3b5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:bug-fill" {...props}></Icon>
