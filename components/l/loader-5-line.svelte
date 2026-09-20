<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sl8-tc6le.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sl8-tc6le"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:loader-5-line" {...props}></Icon>
