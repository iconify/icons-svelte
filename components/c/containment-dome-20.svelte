<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdtcojbje.css';
import '../../css/p/pycxazbfr.css';
import '../../css/e/eepo9qbdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hdtcojbje"/><path class="pycxazbfr"/><path class="eepo9qbdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:containment-dome-20" {...props}></Icon>
