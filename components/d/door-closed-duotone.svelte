<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n0b33wbja.css';
import '../../css/q/qi57hyiwy.css';
import '../../css/x/x33sl95gk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="n0b33wbja"/><path class="qi57hyiwy"/><path class="x33sl95gk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:door-closed-duotone" {...props}></Icon>
