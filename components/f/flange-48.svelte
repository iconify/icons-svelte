<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2g9qy8wl.css';
import '../../css/c/cn-h_ztnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="f2g9qy8wl"/><path class="cn-h_ztnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flange-48" {...props}></Icon>
