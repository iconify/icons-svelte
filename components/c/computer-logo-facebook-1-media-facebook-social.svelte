<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brx-srbpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="brx-srbpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:computer-logo-facebook-1-media-facebook-social" {...props}></Icon>
