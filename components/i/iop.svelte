<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/egi_1pwxy.css';
import '../../css/m/md286fbip.css';
import '../../css/v/vfgn4jl3j.css';
import '../../css/a/aie4qi4ix.css';
import '../../css/e/ew1t3mblt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle class="egi_1pwxy"/><g class="md286fbip"><path class="vfgn4jl3j"/><path class="aie4qi4ix"/><path class="ew1t3mblt"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency-color:iop" {...props}></Icon>
