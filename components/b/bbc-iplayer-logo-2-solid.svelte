<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3sea2bsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v3sea2bsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:bbc-iplayer-logo-2-solid" {...props}></Icon>
