<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/miccwacuq.css';
import '../../css/g/gtqceqbja.css';
import '../../css/f/f8wc0fbln.css';
import '../../css/y/yf8odfm8j.css';
import '../../css/r/ra3z0j7ob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="miccwacuq"/><path class="gtqceqbja"/><path class="f8wc0fbln"/><path class="yf8odfm8j"/><path class="ra3z0j7ob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:minibus-20" {...props}></Icon>
