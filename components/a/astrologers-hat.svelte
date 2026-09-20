<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upnhazbkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="upnhazbkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:astrologers-hat" {...props}></Icon>
