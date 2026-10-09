<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvggpac7z.css';
import '../../css/w/wracacbgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wvggpac7z"/><path class="wracacbgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-droplet-48" {...props}></Icon>
