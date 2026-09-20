<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l55hs8bvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l55hs8bvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-excel-2000-dark" {...props}></Icon>
