<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffrhalb9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ffrhalb9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:magnifying-glass" {...props}></Icon>
