<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e22_hsbig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e22_hsbig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:battery-charging-one" {...props}></Icon>
