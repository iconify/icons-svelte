<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vx5kj2b5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vx5kj2b5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chart-parallel" {...props}></Icon>
