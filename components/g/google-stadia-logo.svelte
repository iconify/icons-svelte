<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvyvww6gd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fvyvww6gd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-stadia-logo" {...props}></Icon>
