<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phlg5e-oi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="phlg5e-oi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:irc-galleria-logo-solid" {...props}></Icon>
