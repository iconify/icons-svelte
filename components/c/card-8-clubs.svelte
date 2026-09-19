<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blzwy-b8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="blzwy-b8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-8-clubs" {...props}></Icon>
