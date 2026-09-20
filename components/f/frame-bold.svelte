<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygrpgv_sq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ygrpgv_sq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:frame-bold" {...props}></Icon>
