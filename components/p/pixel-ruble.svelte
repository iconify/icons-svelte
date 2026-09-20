<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7mix_bdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="p7mix_bdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pixel-ruble" {...props}></Icon>
