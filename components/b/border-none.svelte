<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j39p49b1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="j39p49b1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:border-none" {...props}></Icon>
