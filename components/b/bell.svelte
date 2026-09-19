<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chqo5l8nk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="chqo5l8nk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:bell" {...props}></Icon>
