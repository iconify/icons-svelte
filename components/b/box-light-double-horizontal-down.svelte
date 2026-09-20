<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0_h-gb7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="u0_h-gb7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-double-horizontal-down" {...props}></Icon>
