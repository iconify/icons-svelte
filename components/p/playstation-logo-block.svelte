<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akapamtcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="akapamtcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:playstation-logo-block" {...props}></Icon>
