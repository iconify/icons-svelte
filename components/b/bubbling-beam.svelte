<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8k7air3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u8k7air3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bubbling-beam" {...props}></Icon>
