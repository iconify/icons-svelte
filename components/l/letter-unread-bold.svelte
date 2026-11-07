<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybu95d8og.css';
import '../../css/z/zh2x-vuty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ybu95d8og"/><path clip-rule="evenodd" class="zh2x-vuty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:letter-unread-bold" {...props}></Icon>
