<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/flkqk9ded.css';
import '../../css/l/lj3jycc9m.css';
import '../../css/n/n1kqxqblq.css';
import '../../css/r/r00q4lbzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":301,"height":201};
const content = `<g class="ft5dv1b6b"><path class="flkqk9ded"/><path class="lj3jycc9m"/><path class="n1kqxqblq"/><path class="r00q4lbzd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cif:gm" {...props}></Icon>
