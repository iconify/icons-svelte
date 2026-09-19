<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlfx1wn9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hlfx1wn9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:kevlar-vest" {...props}></Icon>
