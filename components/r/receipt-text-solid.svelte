<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxhdtb-6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxhdtb-6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:receipt-text-solid" {...props}></Icon>
