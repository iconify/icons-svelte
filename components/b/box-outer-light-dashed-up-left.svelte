<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oy616z8bl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="oy616z8bl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-outer-light-dashed-up-left" {...props}></Icon>
