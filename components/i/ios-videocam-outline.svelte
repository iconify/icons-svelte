<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjuulwb_p.css';
import '../../css/i/i60oecb_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bjuulwb_p"/><path class="i60oecb_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-videocam-outline" {...props}></Icon>
