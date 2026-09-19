<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3vijhb2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i3vijhb2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:diagram" {...props}></Icon>
