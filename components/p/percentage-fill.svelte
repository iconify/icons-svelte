<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svgpb476e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="svgpb476e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:percentage-fill" {...props}></Icon>
