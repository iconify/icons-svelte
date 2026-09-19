<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3u4msgjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y3u4msgjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-joker" {...props}></Icon>
