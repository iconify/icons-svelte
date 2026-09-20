<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zklx2bcbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zklx2bcbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:certificate-error-filled" {...props}></Icon>
