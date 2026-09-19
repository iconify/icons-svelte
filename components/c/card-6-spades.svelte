<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tif1ywbpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tif1ywbpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-6-spades" {...props}></Icon>
