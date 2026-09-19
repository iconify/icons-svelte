<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5xktfb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d5xktfb5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cut-lemon" {...props}></Icon>
