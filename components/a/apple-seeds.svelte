<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6tclgh3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h6tclgh3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:apple-seeds" {...props}></Icon>
