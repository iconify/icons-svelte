<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvhz7hd7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kvhz7hd7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:letter-v" {...props}></Icon>
