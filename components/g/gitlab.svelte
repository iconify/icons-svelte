<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rciwx7bwu.css';
import '../../css/y/ym3jfkbrh.css';
import '../../css/r/rmme9m09l.css';
import '../../css/g/g0h8z3bqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="rciwx7bwu"/><path class="ym3jfkbrh"/><path class="rmme9m09l"/><path class="g0h8z3bqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:gitlab" {...props}></Icon>
