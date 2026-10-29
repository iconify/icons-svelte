<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/p/pjfvu7rlw.css';
import '../../css/b/bxjv56brc.css';
import '../../css/j/jdk8orm8z.css';
import '../../css/y/y822yac6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="pjfvu7rlw wm-deco"/><path class="bxjv56brc wm-deco"/><path class="jdk8orm8z"/><path class="y822yac6q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:maximize-2-blueprint" {...props}></Icon>
