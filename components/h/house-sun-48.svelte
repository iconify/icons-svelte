<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvggpac7z.css';
import '../../css/r/rj7hwkb9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wvggpac7z"/><path class="rj7hwkb9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-sun-48" {...props}></Icon>
