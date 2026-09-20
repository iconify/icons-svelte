<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd3qvte3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pd3qvte3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-drive-logo-2-solid" {...props}></Icon>
