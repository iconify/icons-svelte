<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9dv82bum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d9dv82bum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-meet-logo-solid" {...props}></Icon>
