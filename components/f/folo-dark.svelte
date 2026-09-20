<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcpclgb6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zcpclgb6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:folo-dark" {...props}></Icon>
