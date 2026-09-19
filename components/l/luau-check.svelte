<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s53vmbcgz.css';
import '../../css/s/ss6--sbpb.css';
import '../../css/d/d_hbrvb-g.css';
import '../../css/f/fazon-bzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="s53vmbcgz"><path class="ss6--sbpb"/><path class="d_hbrvb-g"/><path class="fazon-bzg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:luau-check" {...props}></Icon>
