<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wi8ammb2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wi8ammb2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-ads-logo-solid" {...props}></Icon>
