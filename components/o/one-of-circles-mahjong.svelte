<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ciu9sjufk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ciu9sjufk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:one-of-circles-mahjong" {...props}></Icon>
