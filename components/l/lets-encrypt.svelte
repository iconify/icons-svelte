<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjtd44buw.css';
import '../../css/t/tkkp7gb-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bjtd44buw"/><path class="tkkp7gb-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lets-encrypt" {...props}></Icon>
