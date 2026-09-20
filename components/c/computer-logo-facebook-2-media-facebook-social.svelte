<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikz5sacwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ikz5sacwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:computer-logo-facebook-2-media-facebook-social" {...props}></Icon>
