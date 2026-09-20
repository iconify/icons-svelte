<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry40d-87g.css';
import '../../css/c/cj-4sbbcy.css';
import '../../css/c/cqj30chyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ry40d-87g"/><path class="cj-4sbbcy"/><path class="cqj30chyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:palette-line" {...props}></Icon>
