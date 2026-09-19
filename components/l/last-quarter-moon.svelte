<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f4h0e5b5l.css';
import '../../css/k/kg8tmobne.css';
import '../../css/j/jwk4qhbzt.css';
import '../../css/n/nmdlyjmlz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="f4h0e5b5l"/><path class="kg8tmobne"/><path class="jwk4qhbzt"/><path class="nmdlyjmlz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:last-quarter-moon" {...props}></Icon>
