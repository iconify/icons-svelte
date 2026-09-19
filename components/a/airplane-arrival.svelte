<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyti6_y5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dyti6_y5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:airplane-arrival" {...props}></Icon>
