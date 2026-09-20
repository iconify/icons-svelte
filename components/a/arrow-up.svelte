<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlw-j5ziv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="mlw-j5ziv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:arrow-up" {...props}></Icon>
