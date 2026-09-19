<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxni6o3aa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxni6o3aa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:grid" {...props}></Icon>
