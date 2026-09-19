<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccaxjcfjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ccaxjcfjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:boot-kick" {...props}></Icon>
