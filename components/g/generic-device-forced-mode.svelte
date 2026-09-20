<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybq7s_syt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ybq7s_syt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:generic-device-forced-mode" {...props}></Icon>
