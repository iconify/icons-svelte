<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/u/u1jwn7bvu.css';
import '../../css/p/ppq-0kb9b.css';
import '../../css/d/dg7qrmb6g.css';
import '../../css/u/ue7lx6y0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="u1jwn7bvu"/><path class="ppq-0kb9b"/><path class="dg7qrmb6g"/><path class="ue7lx6y0z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ai-image" {...props}></Icon>
