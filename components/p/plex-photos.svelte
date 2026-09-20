<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akqouxm0s.css';
import '../../css/n/nscyqnbmh.css';
import '../../css/a/axmh90bqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="akqouxm0s"/><path class="nscyqnbmh"/><path class="axmh90bqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:plex-photos" {...props}></Icon>
