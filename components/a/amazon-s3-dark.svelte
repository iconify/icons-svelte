<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpw_gduhr.css';
import '../../css/m/m-hjm3bkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xpw_gduhr"/><path class="m-hjm3bkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:amazon-s3-dark" {...props}></Icon>
