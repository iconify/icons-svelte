<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvggpac7z.css';
import '../../css/d/ddeq6kb3m.css';
import '../../css/s/sc9dz5b-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wvggpac7z"/><path class="ddeq6kb3m"/><path class="sc9dz5b-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-heat-pump-48" {...props}></Icon>
