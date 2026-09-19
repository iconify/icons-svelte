<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irtgs248t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="irtgs248t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:red-dragon-mahjong-filled" {...props}></Icon>
