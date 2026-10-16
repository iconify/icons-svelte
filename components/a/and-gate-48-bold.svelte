<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7zl_d3jf.css';
import '../../css/p/p7-m9i8me.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d7zl_d3jf"/><path class="p7-m9i8me"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:and-gate-48-bold" {...props}></Icon>
