<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2ysngb0i.css';
import '../../css/e/ejksd6blo.css';
import '../../css/g/gszeo4h3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y2ysngb0i"/><path class="ejksd6blo"/><path class="gszeo4h3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ammonia-tank-48" {...props}></Icon>
