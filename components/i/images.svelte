<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dhm703nga.css';
import '../../css/e/e3a6xsbtr.css';
import '../../css/f/fx8mkab4g.css';
import '../../css/h/hnoua222e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="dhm703nga"/><path class="e3a6xsbtr"/><rect transform="matrix(-1 0 0 -1 28 20)" class="fx8mkab4g"/><path class="hnoua222e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:images" {...props}></Icon>
