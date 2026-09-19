<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9csp_4qz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m9csp_4qz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-king-spades" {...props}></Icon>
