<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcgs8uiau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":374,"height":512};
const content = `<path class="xcgs8uiau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:brotli-old" {...props}></Icon>
