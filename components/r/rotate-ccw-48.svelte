<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfqlvd-8s.css';
import '../../css/k/kaoreac1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xfqlvd-8s"/><path class="kaoreac1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rotate-ccw-48" {...props}></Icon>
