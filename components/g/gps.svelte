<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-0akj67l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p-0akj67l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:gps" {...props}></Icon>
