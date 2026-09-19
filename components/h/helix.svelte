<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kuf42lb8e.css';
import '../../css/h/h32s7pb1r.css';
import '../../css/k/kmg5mtb8s.css';
import '../../css/k/kxdfcnclp.css';
import '../../css/j/j14f6hbti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<g class="kuf42lb8e"><path class="h32s7pb1r"/><path class="kmg5mtb8s"/><path class="kxdfcnclp"/><path class="j14f6hbti"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:helix" {...props}></Icon>
