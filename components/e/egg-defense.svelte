<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgw8ko-wm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qgw8ko-wm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:egg-defense" {...props}></Icon>
