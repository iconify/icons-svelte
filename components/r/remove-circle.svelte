<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dw7p0cfwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="dw7p0cfwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:remove-circle" {...props}></Icon>
