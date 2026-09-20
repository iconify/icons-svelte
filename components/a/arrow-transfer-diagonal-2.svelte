<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cx-wx-b-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="cx-wx-b-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:arrow-transfer-diagonal-2" {...props}></Icon>
