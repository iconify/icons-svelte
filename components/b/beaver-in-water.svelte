<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha54we7vy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ha54we7vy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:beaver-in-water" {...props}></Icon>
