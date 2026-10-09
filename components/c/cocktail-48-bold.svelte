<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0z0h0l9r.css';
import '../../css/n/n3dvw-bko.css';
import '../../css/t/tuurkcb0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="f0z0h0l9r"/><path class="n3dvw-bko"/><path class="tuurkcb0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cocktail-48-bold" {...props}></Icon>
