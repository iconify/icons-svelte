<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/him3u7bwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="him3u7bwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:map" {...props}></Icon>
