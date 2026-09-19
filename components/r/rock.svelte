<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pn3kl9bom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pn3kl9bom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:rock" {...props}></Icon>
