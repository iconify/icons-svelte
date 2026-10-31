<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfintbb9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xfintbb9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:image-sparkle-round" {...props}></Icon>
