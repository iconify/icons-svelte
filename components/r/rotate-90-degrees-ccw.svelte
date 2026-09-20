<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5w8bpbqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f5w8bpbqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:rotate-90-degrees-ccw" {...props}></Icon>
