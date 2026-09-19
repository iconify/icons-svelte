<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogp3kachq.css';
import '../../css/c/ceh3nbbjr.css';
import '../../css/n/nuph4koxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ogp3kachq"/><path class="ceh3nbbjr"/><path class="nuph4koxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:daggerknife" {...props}></Icon>
