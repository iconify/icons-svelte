<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0ns9xbsl.css';
import '../../css/g/grio-8blz.css';
import '../../css/a/aqsnv9bnd.css';
import '../../css/x/x4fp_zoyr.css';
import '../../css/p/prfptqbhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q0ns9xbsl"/><path class="grio-8blz"/><path class="aqsnv9bnd"/><path class="x4fp_zoyr"/><path class="prfptqbhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electric-car-plus-20-bold" {...props}></Icon>
