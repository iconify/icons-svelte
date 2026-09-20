<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjfh3_bxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qjfh3_bxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chart-pie" {...props}></Icon>
