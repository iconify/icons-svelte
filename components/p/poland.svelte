<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtt8ubcij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jtt8ubcij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:poland" {...props}></Icon>
