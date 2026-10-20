<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rthtgrrbd.css';
import '../../css/y/y-pv_ev0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rthtgrrbd"/><path class="y-pv_ev0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:image-sparkle-48" {...props}></Icon>
