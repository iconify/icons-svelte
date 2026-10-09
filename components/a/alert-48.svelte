<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/siuiveb8v.css';
import '../../css/u/uz5vufbgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="siuiveb8v"/><path class="uz5vufbgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:alert-48" {...props}></Icon>
