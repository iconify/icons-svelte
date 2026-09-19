<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xr-on4bcb.css';
import '../../css/u/ubjsthbxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xr-on4bcb"/><path class="ubjsthbxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:my-sql" {...props}></Icon>
