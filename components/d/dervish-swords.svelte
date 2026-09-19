<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-nyycbrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r-nyycbrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:dervish-swords" {...props}></Icon>
