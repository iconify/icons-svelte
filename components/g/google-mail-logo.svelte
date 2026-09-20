<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbe977vdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qbe977vdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-mail-logo" {...props}></Icon>
