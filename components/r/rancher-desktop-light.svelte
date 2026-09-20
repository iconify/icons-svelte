<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqh74goup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xqh74goup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rancher-desktop-light" {...props}></Icon>
