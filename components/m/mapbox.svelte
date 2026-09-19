<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sevo_kb4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sevo_kb4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:mapbox" {...props}></Icon>
