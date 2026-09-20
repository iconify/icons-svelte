<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vubm-y1ib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vubm-y1ib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:picking-path-filled" {...props}></Icon>
