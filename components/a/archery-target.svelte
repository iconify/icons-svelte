<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozdtx1bre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ozdtx1bre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:archery-target" {...props}></Icon>
