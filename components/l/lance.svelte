<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct_ba7b1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="ct_ba7b1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:lance" {...props}></Icon>
