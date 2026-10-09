<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njz8i7bri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="njz8i7bri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-48-bold" {...props}></Icon>
