<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrjxnac0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xrjxnac0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:list-play-filled" {...props}></Icon>
