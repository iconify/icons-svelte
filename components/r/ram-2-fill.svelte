<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wq6mhac5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wq6mhac5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:ram-2-fill" {...props}></Icon>
