<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx-1ftb9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jx-1ftb9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:freedom-dove" {...props}></Icon>
