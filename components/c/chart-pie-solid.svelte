<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyrq5gd4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lyrq5gd4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chart-pie-solid" {...props}></Icon>
