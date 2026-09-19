<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlz7dqbap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wlz7dqbap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:matryoshka-dolls" {...props}></Icon>
