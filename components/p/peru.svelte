<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mw_blcj2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mw_blcj2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:peru" {...props}></Icon>
