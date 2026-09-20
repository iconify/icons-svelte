<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xz89qj44i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xz89qj44i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:anticlockwise-line" {...props}></Icon>
