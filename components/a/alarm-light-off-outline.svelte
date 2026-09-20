<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zefx5bxey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zefx5bxey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alarm-light-off-outline" {...props}></Icon>
