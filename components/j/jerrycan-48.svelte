<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x71_24qub.css';
import '../../css/c/cvi3d18na.css';
import '../../css/x/xpy4gbb2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x71_24qub"/><path class="cvi3d18na"/><path class="xpy4gbb2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:jerrycan-48" {...props}></Icon>
