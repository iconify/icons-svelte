<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lz74811is.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lz74811is"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:meal" {...props}></Icon>
