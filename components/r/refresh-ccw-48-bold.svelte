<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnn54cb4h.css';
import '../../css/m/mhloycbtk.css';
import '../../css/f/fl7_klb8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jnn54cb4h"/><path class="mhloycbtk"/><path class="fl7_klb8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:refresh-ccw-48-bold" {...props}></Icon>
