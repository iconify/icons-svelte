<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pe5m685gm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pe5m685gm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:double-ringed-orb" {...props}></Icon>
