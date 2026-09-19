<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq6t0xbcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eq6t0xbcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cake-slice" {...props}></Icon>
