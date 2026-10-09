<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsiaoacww.css';
import '../../css/q/q5pax_b_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fsiaoacww"/><path class="q5pax_b_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bookmark-check-48" {...props}></Icon>
