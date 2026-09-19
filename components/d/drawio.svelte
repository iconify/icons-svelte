<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ux3o_f6vg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ux3o_f6vg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:drawio" {...props}></Icon>
