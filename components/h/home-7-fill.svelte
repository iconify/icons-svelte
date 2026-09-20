<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipk0zxblz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ipk0zxblz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:home-7-fill" {...props}></Icon>
