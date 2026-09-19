<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzmgk0qpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zzmgk0qpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:admin-page" {...props}></Icon>
