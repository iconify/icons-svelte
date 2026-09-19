<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzthl2mbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tzthl2mbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:chameleon-glyph" {...props}></Icon>
