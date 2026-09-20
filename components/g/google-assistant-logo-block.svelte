<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysun414lb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ysun414lb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-assistant-logo-block" {...props}></Icon>
