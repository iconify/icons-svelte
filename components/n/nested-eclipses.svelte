<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/teov2sdlc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="teov2sdlc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:nested-eclipses" {...props}></Icon>
