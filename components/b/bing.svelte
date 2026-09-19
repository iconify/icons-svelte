<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pquvglb3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pquvglb3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:bing" {...props}></Icon>
