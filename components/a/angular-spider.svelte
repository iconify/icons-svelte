<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m21ieoben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m21ieoben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:angular-spider" {...props}></Icon>
