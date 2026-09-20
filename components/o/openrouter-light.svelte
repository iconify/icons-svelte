<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oayqckbut.css';
import '../../css/l/l2ri-gbnp.css';
import '../../css/z/zkxi6bboz.css';
import '../../css/r/rz2qodbyj.css';
import '../../css/t/t2oa5nb1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<g class="oayqckbut"><path class="l2ri-gbnp"/><path class="zkxi6bboz"/><path class="rz2qodbyj"/><path class="t2oa5nb1m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:openrouter-light" {...props}></Icon>
