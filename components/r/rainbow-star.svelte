<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mom0oactl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mom0oactl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:rainbow-star" {...props}></Icon>
