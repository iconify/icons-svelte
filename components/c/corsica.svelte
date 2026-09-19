<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ym8kz_1yf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ym8kz_1yf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:corsica" {...props}></Icon>
