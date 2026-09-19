<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pj86w2baj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pj86w2baj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:measure-tape" {...props}></Icon>
