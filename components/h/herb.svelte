<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm-fcjqbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rm-fcjqbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:herb" {...props}></Icon>
