<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dk4oliu5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dk4oliu5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:magic-axe" {...props}></Icon>
