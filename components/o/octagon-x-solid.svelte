<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxs67wbpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cxs67wbpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:octagon-x-solid" {...props}></Icon>
