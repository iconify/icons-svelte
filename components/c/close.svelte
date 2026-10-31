<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzd3_cbbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xzd3_cbbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="struq:close" {...props}></Icon>
