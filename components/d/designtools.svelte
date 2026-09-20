<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/lw-gki7ii.css';
import '../../css/b/bb-gp60lh.css';
import '../../css/r/r0csu8bbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lw-gki7ii"/><path class="bb-gp60lh"/><path class="r0csu8bbg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:designtools" {...props}></Icon>
