<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us-c97fhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="us-c97fhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hotel-line" {...props}></Icon>
