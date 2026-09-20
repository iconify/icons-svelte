<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/su3k7ebjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="su3k7ebjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rclone-dark" {...props}></Icon>
