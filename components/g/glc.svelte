<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6_mqv_xj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t6_mqv_xj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:glc" {...props}></Icon>
