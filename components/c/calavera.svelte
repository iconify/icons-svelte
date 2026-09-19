<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blmhbm1pl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="blmhbm1pl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:calavera" {...props}></Icon>
