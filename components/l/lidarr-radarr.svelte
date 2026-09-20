<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-wkamaxf.css';
import '../../css/s/s6yebsb7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a-wkamaxf"/><path class="s6yebsb7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lidarr-radarr" {...props}></Icon>
