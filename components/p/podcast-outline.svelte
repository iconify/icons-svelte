<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/x/x7ptq8p-g.css';
import '../../css/z/zm--xre6q.css';
import '../../css/c/ca7cldnps.css';
import '../../css/m/mhekwub7m.css';
import '../../css/p/ps9jkkbrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><rect class="x7ptq8p-g"/><path class="zm--xre6q"/><path class="ca7cldnps"/><path class="mhekwub7m"/><path class="ps9jkkbrq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:podcast-outline" {...props}></Icon>
