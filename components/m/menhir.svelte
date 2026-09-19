<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbdq3lbhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dbdq3lbhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:menhir" {...props}></Icon>
