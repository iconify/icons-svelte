<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0phu2bbs.css';
import '../../css/m/m2aoc-b8l.css';
import '../../css/r/r3yep8gbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="m2aoc-b8l"/><path class="r3yep8gbg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:check-circle-2-bold" {...props}></Icon>
