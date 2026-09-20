<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akqouxm0s.css';
import '../../css/i/iz4-9bcxw.css';
import '../../css/k/kvfbqsbck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="akqouxm0s"/><path class="iz4-9bcxw"/><path class="kvfbqsbck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:plex-dash" {...props}></Icon>
