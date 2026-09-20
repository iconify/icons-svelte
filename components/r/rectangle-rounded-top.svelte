<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fb_-eibnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fb_-eibnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:rectangle-rounded-top" {...props}></Icon>
