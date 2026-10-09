<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlmlrhbpp.css';
import '../../css/c/cyronpb3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zlmlrhbpp"/><path class="cyronpb3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:charity-48-bold" {...props}></Icon>
