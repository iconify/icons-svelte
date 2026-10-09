<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vghbbfb2f.css';
import '../../css/p/pw56fm25u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vghbbfb2f"/><path class="pw56fm25u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pellet-boiler-48" {...props}></Icon>
