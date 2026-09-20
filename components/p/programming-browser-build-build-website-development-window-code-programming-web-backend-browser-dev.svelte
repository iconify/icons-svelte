<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mo6pl3bui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="mo6pl3bui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:programming-browser-build-build-website-development-window-code-programming-web-backend-browser-dev" {...props}></Icon>
