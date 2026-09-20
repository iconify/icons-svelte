<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcuck66nd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pcuck66nd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-compress-up" {...props}></Icon>
