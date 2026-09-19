<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hefd2s-6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hefd2s-6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-queen-diamonds" {...props}></Icon>
