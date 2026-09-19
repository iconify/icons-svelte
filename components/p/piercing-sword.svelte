<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx_m927ii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nx_m927ii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:piercing-sword" {...props}></Icon>
