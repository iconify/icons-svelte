<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llgm2lbfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="llgm2lbfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:adobe-after-effects-logo-solid" {...props}></Icon>
