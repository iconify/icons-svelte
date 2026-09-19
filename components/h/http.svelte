<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp7upebym.css';
import '../../css/r/rirt7bcol.css';
import '../../css/j/jdk23lb_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="xp7upebym"><path class="rirt7bcol"/><path class="jdk23lb_l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:http" {...props}></Icon>
