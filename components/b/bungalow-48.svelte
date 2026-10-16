<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsfzl1bhj.css';
import '../../css/d/dtsd2ea6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rsfzl1bhj"/><path class="dtsd2ea6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bungalow-48" {...props}></Icon>
