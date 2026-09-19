<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di_02ys5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="di_02ys5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:head-shot" {...props}></Icon>
