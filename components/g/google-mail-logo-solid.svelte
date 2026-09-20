<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqt-0cbly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vqt-0cbly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-mail-logo-solid" {...props}></Icon>
