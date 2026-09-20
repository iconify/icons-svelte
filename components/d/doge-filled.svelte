<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp2pneo0a.css';
import '../../css/p/p76fyjzyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xp2pneo0a"/><path class="p76fyjzyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:doge-filled" {...props}></Icon>
