<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv26jgn9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yv26jgn9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:nest-gateway" {...props}></Icon>
