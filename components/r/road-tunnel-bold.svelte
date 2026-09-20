<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdjxh7b1z.css';
import '../../css/u/utq4fcbnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hdjxh7b1z"/><path class="utq4fcbnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:road-tunnel-bold" {...props}></Icon>
