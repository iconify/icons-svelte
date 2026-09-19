<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvdcfhufs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="vvdcfhufs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:github-text" {...props}></Icon>
