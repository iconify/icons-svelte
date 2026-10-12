<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohs7hsjpb.css';
import '../../css/s/sdzy7xbyh.css';
import '../../css/x/xn0bb9b4d.css';
import '../../css/y/y97xnkbid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ohs7hsjpb"/><path class="sdzy7xbyh"/><path class="xn0bb9b4d"/><path class="y97xnkbid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ambulance-48" {...props}></Icon>
