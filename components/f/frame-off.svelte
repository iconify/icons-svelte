<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2vz0_yun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i2vz0_yun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:frame-off" {...props}></Icon>
