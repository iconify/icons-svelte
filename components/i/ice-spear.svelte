<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqge1p_bt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iqge1p_bt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ice-spear" {...props}></Icon>
