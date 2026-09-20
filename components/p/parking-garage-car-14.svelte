<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/geth3h_ed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="geth3h_ed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:parking-garage-car-14" {...props}></Icon>
