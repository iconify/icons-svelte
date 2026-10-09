<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsiaoacww.css';
import '../../css/p/pe35xebhe.css';
import '../../css/u/um7q16f0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fsiaoacww"/><path class="pe35xebhe"/><path class="um7q16f0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bookmark-plus-48" {...props}></Icon>
