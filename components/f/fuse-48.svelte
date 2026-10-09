<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulm7ljbga.css';
import '../../css/p/pfm3u1bvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ulm7ljbga"/><path class="pfm3u1bvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fuse-48" {...props}></Icon>
