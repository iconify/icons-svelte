<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgfx4-byf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="pgfx4-byf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:area-chart" {...props}></Icon>
