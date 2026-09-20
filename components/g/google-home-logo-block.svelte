<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cy7gu6zfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cy7gu6zfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-home-logo-block" {...props}></Icon>
