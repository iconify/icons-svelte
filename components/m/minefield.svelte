<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkdvj_bfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gkdvj_bfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:minefield" {...props}></Icon>
