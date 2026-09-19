<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jowh1fb9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jowh1fb9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:clapperboard" {...props}></Icon>
