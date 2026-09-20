<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xr_-_c70n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xr_-_c70n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:maintenance-documents" {...props}></Icon>
