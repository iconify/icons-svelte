<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywx0g0bvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ywx0g0bvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:barbecue" {...props}></Icon>
