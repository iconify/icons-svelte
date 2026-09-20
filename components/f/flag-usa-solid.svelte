<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lp_djx_7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lp_djx_7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:flag-usa-solid" {...props}></Icon>
