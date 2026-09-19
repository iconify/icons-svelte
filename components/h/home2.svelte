<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dl5sv6bqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dl5sv6bqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:home2" {...props}></Icon>
