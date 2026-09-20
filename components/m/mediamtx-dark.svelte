<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yx8_exglu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yx8_exglu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mediamtx-dark" {...props}></Icon>
