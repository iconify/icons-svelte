<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/l/ll9oracgz.css';
import '../../css/d/dqytk5brb.css';
import '../../css/g/gmyf6120p.css';
import '../../css/s/s9_882qzo.css';
import '../../css/g/gi6gjccot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="ll9oracgz wm-deco"/><path class="dqytk5brb wm-deco"/><path class="gmyf6120p wm-k"/><path class="s9_882qzo wm-a"/><path class="gi6gjccot wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:laptop-blueprint" {...props}></Icon>
