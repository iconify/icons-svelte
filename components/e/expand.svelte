<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c51pwqbgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c51pwqbgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:expand" {...props}></Icon>
