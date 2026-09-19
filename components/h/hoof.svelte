<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tav2-pbmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tav2-pbmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:hoof" {...props}></Icon>
