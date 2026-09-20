<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9f7cs6wj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="r9f7cs6wj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:alpha-k-fill" {...props}></Icon>
