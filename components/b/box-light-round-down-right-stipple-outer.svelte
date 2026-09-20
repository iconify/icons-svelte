<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4dlh8bkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="r4dlh8bkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-round-down-right-stipple-outer" {...props}></Icon>
