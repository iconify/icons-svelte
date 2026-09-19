<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hs58xacvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hs58xacvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fuel-tank" {...props}></Icon>
