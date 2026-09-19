<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgtjkzq3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xgtjkzq3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:apple" {...props}></Icon>
