<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxp70fsne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wxp70fsne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fried-eggs" {...props}></Icon>
