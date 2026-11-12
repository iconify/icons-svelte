<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvf2hdcms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wvf2hdcms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:omada-dark" {...props}></Icon>
