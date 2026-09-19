<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d24qi6xmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d24qi6xmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:entangled-typhoon" {...props}></Icon>
