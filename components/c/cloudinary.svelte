<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ne_6bfb2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ne_6bfb2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:cloudinary" {...props}></Icon>
