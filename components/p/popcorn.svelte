<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_ghg35vl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t_ghg35vl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:popcorn" {...props}></Icon>
