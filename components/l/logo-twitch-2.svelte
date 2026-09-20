<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8rru2b7i.css';
import '../../css/d/dwn288bus.css';
import '../../css/g/gddrajlcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p8rru2b7i"/><path class="dwn288bus"/><path class="gddrajlcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:logo-twitch-2" {...props}></Icon>
