<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/g/gmaum8vqc.css';
import '../../css/g/ghb9m550i.css';
import '../../css/o/ot_m0hbva.css';
import '../../css/r/rmwwbubll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="gmaum8vqc"/><path class="ghb9m550i"/><path class="ot_m0hbva"/><path class="rmwwbubll"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:backpack-01" {...props}></Icon>
