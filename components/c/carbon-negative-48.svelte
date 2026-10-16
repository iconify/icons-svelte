<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbiesybpo.css';
import '../../css/h/hxd8jsd4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dbiesybpo"/><path class="hxd8jsd4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:carbon-negative-48" {...props}></Icon>
