<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fn1tm3vbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fn1tm3vbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:metal-bar" {...props}></Icon>
