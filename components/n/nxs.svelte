<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywgnk_p2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ywgnk_p2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:nxs" {...props}></Icon>
