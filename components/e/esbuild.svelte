<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u41s7qbwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u41s7qbwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:esbuild" {...props}></Icon>
