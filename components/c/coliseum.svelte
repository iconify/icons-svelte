<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scoj68s8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="scoj68s8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:coliseum" {...props}></Icon>
