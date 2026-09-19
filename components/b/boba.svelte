<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y--m3f9qp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y--m3f9qp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:boba" {...props}></Icon>
