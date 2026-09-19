<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtmerfb1q.css';
import '../../css/f/fig7n4w6p.css';
import '../../css/u/utvn67bmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jtmerfb1q"/><path class="fig7n4w6p"/><path class="utvn67bmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:folder-assets-open" {...props}></Icon>
