<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ee5gdzt4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ee5gdzt4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:rogue" {...props}></Icon>
