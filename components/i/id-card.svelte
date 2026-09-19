<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di5vm559l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="di5vm559l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:id-card" {...props}></Icon>
