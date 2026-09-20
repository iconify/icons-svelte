<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ov7mw7bgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ov7mw7bgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-hangouts-meet-logo-block" {...props}></Icon>
