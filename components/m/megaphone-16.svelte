<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzi7zfbtp.css';
import '../../css/f/fh60u4boo.css';
import '../../css/c/cnio1-a_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tzi7zfbtp"/><path class="fh60u4boo"/><path class="cnio1-a_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:megaphone-16" {...props}></Icon>
