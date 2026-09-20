<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxl_0ldls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxl_0ldls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cloud-snow-fill" {...props}></Icon>
