<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srmecmdfr.css';
import '../../css/d/d7nxq5b8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="srmecmdfr"/><path class="d7nxq5b8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:air-quality-20-bold" {...props}></Icon>
