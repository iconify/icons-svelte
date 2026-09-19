<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fr3o_bcsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fr3o_bcsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:louvre-pyramid" {...props}></Icon>
