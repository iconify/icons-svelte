<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvfqs5zsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zvfqs5zsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:graveyard" {...props}></Icon>
