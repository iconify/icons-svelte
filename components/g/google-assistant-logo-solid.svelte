<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isyypmjxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="isyypmjxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-assistant-logo-solid" {...props}></Icon>
