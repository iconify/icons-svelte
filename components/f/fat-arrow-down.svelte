<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kg3ameb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kg3ameb8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:fat-arrow-down" {...props}></Icon>
