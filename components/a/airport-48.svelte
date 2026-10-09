<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iij7ri-7j.css';
import '../../css/k/k_0c2xn7m.css';
import '../../css/s/st8n3_8ji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="iij7ri-7j"/><path class="k_0c2xn7m"/><path class="st8n3_8ji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:airport-48" {...props}></Icon>
