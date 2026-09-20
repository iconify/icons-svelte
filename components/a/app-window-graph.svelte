<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wceggdbtg.css';
import '../../css/i/ingyikb1h.css';
import '../../css/u/u0csdv95s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wceggdbtg"/><path class="ingyikb1h"/><path class="u0csdv95s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:app-window-graph" {...props}></Icon>
