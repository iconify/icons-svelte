<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpi-8x__k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fpi-8x__k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:oil-spill-48-bold" {...props}></Icon>
