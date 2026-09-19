<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wry-t2b-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wry-t2b-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:robin-hood-hat" {...props}></Icon>
