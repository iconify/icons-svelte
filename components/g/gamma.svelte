<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh5l4yp3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="rh5l4yp3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:gamma" {...props}></Icon>
