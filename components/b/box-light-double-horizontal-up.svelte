<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwi067x_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="vwi067x_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-double-horizontal-up" {...props}></Icon>
