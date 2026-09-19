<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yt2r9xb_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yt2r9xb_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:lightning-1-bold" {...props}></Icon>
