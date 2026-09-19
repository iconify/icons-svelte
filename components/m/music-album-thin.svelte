<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/h/h_tsn8bxt.css';
import '../../css/f/f8ce6t1vq.css';
import '../../css/k/kzx7z1bpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="h_tsn8bxt"/><circle class="f8ce6t1vq"/><path class="kzx7z1bpv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:music-album-thin" {...props}></Icon>
