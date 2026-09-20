<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3srz291p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m3srz291p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:dribbble-solid" {...props}></Icon>
