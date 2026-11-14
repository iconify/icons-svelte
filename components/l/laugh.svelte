<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/g/gvj669z4w.css';
import '../../css/t/tuef6sb5w.css';
import '../../css/r/r6k04cbja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="gvj669z4w"/><path class="tuef6sb5w"/><circle class="r6k04cbja"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:laugh" {...props}></Icon>
