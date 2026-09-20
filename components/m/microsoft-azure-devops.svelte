<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dib2neggl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dib2neggl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:microsoft-azure-devops" {...props}></Icon>
