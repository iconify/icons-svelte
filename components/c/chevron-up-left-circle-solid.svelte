<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgumkvmxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mgumkvmxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chevron-up-left-circle-solid" {...props}></Icon>
