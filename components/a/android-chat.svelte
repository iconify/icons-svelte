<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2lktqd8u.css';
import '../../css/e/ejs_3u14j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g2lktqd8u"/><path class="ejs_3u14j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-chat" {...props}></Icon>
