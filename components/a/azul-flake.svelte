<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npdk0lbct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="npdk0lbct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:azul-flake" {...props}></Icon>
