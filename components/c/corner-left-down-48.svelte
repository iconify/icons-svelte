<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5xf0acau.css';
import '../../css/k/kf6co47ks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y5xf0acau"/><path class="kf6co47ks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:corner-left-down-48" {...props}></Icon>
