<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r97h_xb2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r97h_xb2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:leftright" {...props}></Icon>
