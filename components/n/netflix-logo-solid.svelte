<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzqnoccyv.css';
import '../../css/z/z91rwbb8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pzqnoccyv"/><path clip-rule="evenodd" class="z91rwbb8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:netflix-logo-solid" {...props}></Icon>
