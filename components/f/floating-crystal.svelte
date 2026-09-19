<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uo856qbro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uo856qbro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:floating-crystal" {...props}></Icon>
