<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evnrzabrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="evnrzabrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pick-of-destiny" {...props}></Icon>
