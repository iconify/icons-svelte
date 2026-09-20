<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fb571flvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fb571flvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:linkedin-box-fill" {...props}></Icon>
