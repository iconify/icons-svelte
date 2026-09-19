<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zaz_ppzod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zaz_ppzod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ice-cream-04" {...props}></Icon>
