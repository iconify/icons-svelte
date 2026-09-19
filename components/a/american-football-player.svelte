<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ree4tyblg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ree4tyblg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:american-football-player" {...props}></Icon>
