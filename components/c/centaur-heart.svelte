<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3e0tcciy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u3e0tcciy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:centaur-heart" {...props}></Icon>
