<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l03wl_bfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l03wl_bfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:jungle" {...props}></Icon>
