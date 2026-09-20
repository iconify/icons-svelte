<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dashfabdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dashfabdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:narrow-gauge" {...props}></Icon>
