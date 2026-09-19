<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhb8c01ug.css';
import '../../css/y/yeq9_s_cg.css';
import '../../css/c/c1y_6pbkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="hhb8c01ug"><path class="yeq9_s_cg"/><path class="c1y_6pbkx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:reason" {...props}></Icon>
