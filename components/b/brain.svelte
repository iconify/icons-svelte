<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/t/tddl24bqp.css';
import '../../css/g/g5wy8tb4y.css';
import '../../css/k/kvjcaymdv.css';
import '../../css/j/jsxg4l9cg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="tddl24bqp wm-shadow"/><path class="g5wy8tb4y wm-shadow"/><path class="kvjcaymdv"/><path class="jsxg4l9cg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:brain" {...props}></Icon>
