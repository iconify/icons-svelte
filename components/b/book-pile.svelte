<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plinxxrix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="plinxxrix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:book-pile" {...props}></Icon>
