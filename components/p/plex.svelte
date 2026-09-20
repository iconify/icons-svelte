<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wckuc9nmc.css';
import '../../css/h/hze02wt4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="wckuc9nmc"/><path class="hze02wt4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:plex" {...props}></Icon>
