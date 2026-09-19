<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0q32_b2b.css';
import '../../css/d/dzv7sjbhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m0q32_b2b"/><path class="dzv7sjbhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:rokit" {...props}></Icon>
