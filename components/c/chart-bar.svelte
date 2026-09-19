<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8x1c9bmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k8x1c9bmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:chart-bar" {...props}></Icon>
