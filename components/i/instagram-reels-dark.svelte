<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yj7wg2bbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yj7wg2bbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:instagram-reels-dark" {...props}></Icon>
