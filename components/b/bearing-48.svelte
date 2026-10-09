<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2g9qy8wl.css';
import '../../css/x/x89mfs52m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="f2g9qy8wl"/><path class="x89mfs52m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bearing-48" {...props}></Icon>
