<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqo5wlb-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bqo5wlb-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:octobot-light" {...props}></Icon>
