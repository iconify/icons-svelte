<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unz_1ke_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="unz_1ke_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cubeforce" {...props}></Icon>
