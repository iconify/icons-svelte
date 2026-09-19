<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/b1irycc-s.css';
import '../../css/k/ktxr1u0rx.css';
import '../../css/e/e82etfbzy.css';
import '../../css/u/uujeagbzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="b1irycc-s"/><path class="ktxr1u0rx"/><path class="e82etfbzy"/><path class="uujeagbzt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:headphone-sound" {...props}></Icon>
