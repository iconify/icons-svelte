<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u14q8ob4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u14q8ob4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:mortar" {...props}></Icon>
