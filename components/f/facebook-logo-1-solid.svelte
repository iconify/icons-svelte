<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xipoyr8pe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xipoyr8pe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:facebook-logo-1-solid" {...props}></Icon>
