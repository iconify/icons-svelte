<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar_uynbie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ar_uynbie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:picking-guidance-outline" {...props}></Icon>
