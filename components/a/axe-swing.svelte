<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tuvh94biq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tuvh94biq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:axe-swing" {...props}></Icon>
