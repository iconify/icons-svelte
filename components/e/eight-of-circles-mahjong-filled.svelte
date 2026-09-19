<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_vkl9uws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="c_vkl9uws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:eight-of-circles-mahjong-filled" {...props}></Icon>
