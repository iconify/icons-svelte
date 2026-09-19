<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwc01_3ak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nwc01_3ak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:backward-time" {...props}></Icon>
