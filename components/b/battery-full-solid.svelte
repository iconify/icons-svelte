<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uv-dhlzga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uv-dhlzga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:battery-full-solid" {...props}></Icon>
