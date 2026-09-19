<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzc54yuhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mzc54yuhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cannon" {...props}></Icon>
