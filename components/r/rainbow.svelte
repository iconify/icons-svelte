<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3dxnxzfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3dxnxzfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:rainbow" {...props}></Icon>
