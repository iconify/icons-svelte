<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rx1d-z-yo.css';
import '../../css/g/gvnofzq5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rx1d-z-yo"/><path class="gvnofzq5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrows-vertical-48" {...props}></Icon>
