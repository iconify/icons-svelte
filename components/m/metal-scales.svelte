<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlbqq21ap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wlbqq21ap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:metal-scales" {...props}></Icon>
