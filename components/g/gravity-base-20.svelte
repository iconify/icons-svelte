<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opebgib4l.css';
import '../../css/o/o92awt_ps.css';
import '../../css/p/pycxazbfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="opebgib4l"/><path class="o92awt_ps"/><path class="pycxazbfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gravity-base-20" {...props}></Icon>
