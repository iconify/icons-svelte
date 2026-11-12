<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7a2wvbzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d7a2wvbzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-bing-light" {...props}></Icon>
