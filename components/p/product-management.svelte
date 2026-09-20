<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkmclvb3d.css';
import '../../css/a/acxt2achp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zkmclvb3d"/><path class="acxt2achp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:product-management" {...props}></Icon>
