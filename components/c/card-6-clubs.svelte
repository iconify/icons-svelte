<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7s0drb6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u7s0drb6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-6-clubs" {...props}></Icon>
