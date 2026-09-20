<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/f/fzq72nb8g.css';
import '../../css/c/cu3-8sblw.css';
import '../../css/g/g3oaxt9cr.css';
import '../../css/d/dgzq6fb_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="fzq72nb8g"/><path class="cu3-8sblw"/><path class="g3oaxt9cr"/><path clip-rule="evenodd" class="dgzq6fb_u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:door-open-sharp-duotone" {...props}></Icon>
