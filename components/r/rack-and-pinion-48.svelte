<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nj8ilnbfl.css';
import '../../css/t/t4mrhvxik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nj8ilnbfl"/><path class="t4mrhvxik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rack-and-pinion-48" {...props}></Icon>
