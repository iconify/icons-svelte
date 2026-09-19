<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zy7o6izzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zy7o6izzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:crystal" {...props}></Icon>
