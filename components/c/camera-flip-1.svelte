<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/t/t2zaifbda.css';
import '../../css/r/rnb8pybkj.css';
import '../../css/l/le33cfb2c.css';
import '../../css/r/r2eztqbdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="t2zaifbda"/><path class="rnb8pybkj"/><path class="le33cfb2c"/><path class="r2eztqbdd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:camera-flip-1" {...props}></Icon>
