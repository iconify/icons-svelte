<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xr9wr-bhx.css';
import '../../css/b/bd8f5nbwf.css';
import '../../css/m/mabwzbbvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xr9wr-bhx"/><circle class="bd8f5nbwf"/><path class="mabwzbbvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:info-circle" {...props}></Icon>
