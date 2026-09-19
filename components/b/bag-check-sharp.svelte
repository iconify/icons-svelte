<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wnge6pbba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wnge6pbba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:bag-check-sharp" {...props}></Icon>
