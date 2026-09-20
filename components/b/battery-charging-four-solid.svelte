<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdt01_b4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pdt01_b4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:battery-charging-four-solid" {...props}></Icon>
