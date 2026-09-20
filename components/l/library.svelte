<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpp1e8baq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vpp1e8baq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:library" {...props}></Icon>
