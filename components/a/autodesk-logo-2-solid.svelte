<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgz1uxb6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sgz1uxb6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:autodesk-logo-2-solid" {...props}></Icon>
