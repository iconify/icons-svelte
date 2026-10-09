<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pi--ru22u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pi--ru22u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:laptop-48" {...props}></Icon>
