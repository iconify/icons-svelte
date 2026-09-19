<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u497zqblr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u497zqblr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:inverted-dice-1" {...props}></Icon>
