<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv5slx5dp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zv5slx5dp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:align-horizontal-center-bold" {...props}></Icon>
