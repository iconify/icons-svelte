<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/e6zn6abhh.css';
import '../../css/q/q_f8gu14x.css';
import '../../css/g/gcioct8bz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="e6zn6abhh"/><path class="q_f8gu14x"/><path class="gcioct8bz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:pizza-slice" {...props}></Icon>
