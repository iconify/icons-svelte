<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3b9acb4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f3b9acb4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:network-line" {...props}></Icon>
