<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/js-wdwglr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="js-wdwglr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:magnet-man" {...props}></Icon>
