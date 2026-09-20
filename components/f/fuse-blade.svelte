<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4n0gtbvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a4n0gtbvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fuse-blade" {...props}></Icon>
