<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfpjugbvy.css';
import '../../css/g/gswiw2jgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vfpjugbvy"/><path class="gswiw2jgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-bolt-48-bold" {...props}></Icon>
