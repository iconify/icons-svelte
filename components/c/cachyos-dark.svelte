<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yctzcpbgd.css';
import '../../css/c/cmsj9noho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yctzcpbgd"/><path class="cmsj9noho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cachyos-dark" {...props}></Icon>
