<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fur9vwhrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fur9vwhrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:crossed-sabres" {...props}></Icon>
