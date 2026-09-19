<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjs4webtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rjs4webtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:paper-bag-open" {...props}></Icon>
