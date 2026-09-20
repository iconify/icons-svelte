<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbfn4gbff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbfn4gbff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-assistant-logo" {...props}></Icon>
