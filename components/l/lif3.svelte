<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmzn76hxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kmzn76hxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:lif3" {...props}></Icon>
