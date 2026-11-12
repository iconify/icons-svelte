<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3l_n81lx.css';
import '../../css/u/ubgppxb0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s3l_n81lx"/><path class="ubgppxb0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:oak-identity-dark" {...props}></Icon>
