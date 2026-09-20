<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imx0tq8pe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="imx0tq8pe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:pause" {...props}></Icon>
