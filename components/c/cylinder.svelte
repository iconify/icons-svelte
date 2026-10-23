<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbtj98ggr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wbtj98ggr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:cylinder" {...props}></Icon>
