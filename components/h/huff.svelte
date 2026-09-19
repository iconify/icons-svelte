<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdggcu0gw.css';
import '../../css/s/sljodwyif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rdggcu0gw"/><path class="sljodwyif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:huff" {...props}></Icon>
