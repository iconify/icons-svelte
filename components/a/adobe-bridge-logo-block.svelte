<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwau4g8cd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rwau4g8cd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:adobe-bridge-logo-block" {...props}></Icon>
