<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xh1z0fbeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xh1z0fbeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pirate-hat" {...props}></Icon>
