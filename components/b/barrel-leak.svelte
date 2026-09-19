<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntwqhbbit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ntwqhbbit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:barrel-leak" {...props}></Icon>
