<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kiwwtpb0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="kiwwtpb0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:hospital" {...props}></Icon>
