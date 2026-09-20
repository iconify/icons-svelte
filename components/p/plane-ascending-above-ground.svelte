<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/laz_kgnaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="laz_kgnaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:plane-ascending-above-ground" {...props}></Icon>
