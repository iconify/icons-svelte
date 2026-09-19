<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rynp_kb5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rynp_kb5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:fvm" {...props}></Icon>
