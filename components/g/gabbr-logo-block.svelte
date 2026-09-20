<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgu2rxbut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rgu2rxbut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:gabbr-logo-block" {...props}></Icon>
