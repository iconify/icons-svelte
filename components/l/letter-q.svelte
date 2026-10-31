<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxroi0ylq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mxroi0ylq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:letter-q" {...props}></Icon>
