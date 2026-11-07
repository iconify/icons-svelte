<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-sogubpk.css';
import '../../css/k/kob3fcbmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-sogubpk"/><path class="kob3fcbmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:minimize-bold" {...props}></Icon>
