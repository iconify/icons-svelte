<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mm_hg97ya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mm_hg97ya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:mounted-knight" {...props}></Icon>
