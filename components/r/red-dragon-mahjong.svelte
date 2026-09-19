<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f46e_xbgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="f46e_xbgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:red-dragon-mahjong" {...props}></Icon>
