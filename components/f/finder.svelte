<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckhg4cclh.css';
import '../../css/l/l6od3hn3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":465,"height":512};
const content = `<path class="ckhg4cclh"/><path class="l6od3hn3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:finder" {...props}></Icon>
