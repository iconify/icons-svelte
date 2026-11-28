<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4n5t0rhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u4n5t0rhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:file-chart-plus" {...props}></Icon>
