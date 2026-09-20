<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckkr5xbvl.css';
import '../../css/z/zp5j1oj1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ckkr5xbvl"/><path class="zp5j1oj1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:charles-schwab" {...props}></Icon>
