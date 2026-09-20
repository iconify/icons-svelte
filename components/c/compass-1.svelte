<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmhtbu2jq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xmhtbu2jq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:compass-1" {...props}></Icon>
