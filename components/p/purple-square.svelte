<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vo71evf5d.css';
import '../../css/t/tbzab391z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="vo71evf5d"/><path class="tbzab391z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:purple-square" {...props}></Icon>
