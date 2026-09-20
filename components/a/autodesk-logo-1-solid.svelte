<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4riv7b8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w4riv7b8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:autodesk-logo-1-solid" {...props}></Icon>
