<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsi11wb7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hsi11wb7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:key-lock" {...props}></Icon>
