<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ps_blzb1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ps_blzb1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:magic-swirl" {...props}></Icon>
