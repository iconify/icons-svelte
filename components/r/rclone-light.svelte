<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enjks7vil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="enjks7vil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rclone-light" {...props}></Icon>
