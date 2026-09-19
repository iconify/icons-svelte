<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8_ww-5zf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y8_ww-5zf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:gloop" {...props}></Icon>
