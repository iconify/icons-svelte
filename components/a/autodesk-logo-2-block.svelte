<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhtm67gul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zhtm67gul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:autodesk-logo-2-block" {...props}></Icon>
