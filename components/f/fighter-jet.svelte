<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7ycpab4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z7ycpab4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:fighter-jet" {...props}></Icon>
