<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pg058abpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pg058abpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:oden" {...props}></Icon>
