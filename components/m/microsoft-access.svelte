<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5ewujben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n5ewujben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:microsoft-access" {...props}></Icon>
