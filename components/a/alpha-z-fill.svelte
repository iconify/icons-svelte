<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0cpzlb9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="j0cpzlb9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:alpha-z-fill" {...props}></Icon>
