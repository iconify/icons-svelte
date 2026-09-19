<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agu2bybpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="agu2bybpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:hourglass" {...props}></Icon>
