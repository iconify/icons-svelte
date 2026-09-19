<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7pa8lbuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c7pa8lbuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:look-at" {...props}></Icon>
