<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogvd8x0ke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ogvd8x0ke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:blackball" {...props}></Icon>
