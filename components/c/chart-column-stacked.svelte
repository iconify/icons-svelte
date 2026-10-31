<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/f/f5ezvhpol.css';
import '../../css/q/qij50sb9d.css';
import '../../css/s/sbc5a8b2s.css';
import '../../css/j/j5erqwb9a.css';
import '../../css/x/xla8u0ljy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="f5ezvhpol wm-shadow"/><path class="qij50sb9d"/><path class="sbc5a8b2s"/><path class="j5erqwb9a"/><path class="xla8u0ljy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-retro:chart-column-stacked" {...props}></Icon>
