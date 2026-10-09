<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khd4an8mp.css';
import '../../css/k/k98e3f_0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="khd4an8mp"/><path class="k98e3f_0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:droplet-48-bold" {...props}></Icon>
