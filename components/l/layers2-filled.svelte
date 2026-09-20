<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bub8qccmg.css';
import '../../css/d/dbifspbys.css';
import '../../css/c/cdp_3db-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bub8qccmg"/><path class="dbifspbys"/><path class="cdp_3db-d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:layers2-filled" {...props}></Icon>
