<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfsyys30a.css';
import '../../css/h/hti4-6bvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wfsyys30a"/><path class="hti4-6bvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gearbox-20" {...props}></Icon>
