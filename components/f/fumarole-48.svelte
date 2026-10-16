<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdsbxfwgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zdsbxfwgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fumarole-48" {...props}></Icon>
