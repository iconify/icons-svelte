<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rt_364k4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="rt_364k4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:arrow-up-box" {...props}></Icon>
