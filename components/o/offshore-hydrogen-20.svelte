<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qorl_g63f.css';
import '../../css/m/m2pt6cjck.css';
import '../../css/o/okdvo848h.css';
import '../../css/p/pycxazbfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qorl_g63f"/><path class="m2pt6cjck"/><path class="okdvo848h"/><path class="pycxazbfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:offshore-hydrogen-20" {...props}></Icon>
