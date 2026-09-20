<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3qiiwdfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k3qiiwdfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:microsoft-yammer" {...props}></Icon>
