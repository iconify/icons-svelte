<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbd3abb2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xbd3abb2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:microsoft-windows-logo-3" {...props}></Icon>
