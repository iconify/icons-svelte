<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqoz3rbch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xqoz3rbch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pierced-heart" {...props}></Icon>
