<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bot_9nbfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bot_9nbfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:comment-dollar" {...props}></Icon>
