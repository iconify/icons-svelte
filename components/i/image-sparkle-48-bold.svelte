<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcfuqov3g.css';
import '../../css/w/wb2m571ci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gcfuqov3g"/><path class="wb2m571ci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:image-sparkle-48-bold" {...props}></Icon>
