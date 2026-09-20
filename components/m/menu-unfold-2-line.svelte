<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yph7yabcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yph7yabcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:menu-unfold-2-line" {...props}></Icon>
