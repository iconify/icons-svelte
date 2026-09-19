<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ro0w3__dv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ro0w3__dv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:hooded-assassin" {...props}></Icon>
