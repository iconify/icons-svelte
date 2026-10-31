<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6emu6ghc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m6emu6ghc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bluetooth-gloss" {...props}></Icon>
