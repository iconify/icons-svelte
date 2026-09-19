<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inob4lces.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="inob4lces"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-2-diamonds" {...props}></Icon>
