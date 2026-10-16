<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/neu7wrbqd.css';
import '../../css/c/cero_9xdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="neu7wrbqd"/><path class="cero_9xdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:meter-cabinet-48" {...props}></Icon>
