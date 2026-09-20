<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jio9igvay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jio9igvay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:antenna-bars-4" {...props}></Icon>
