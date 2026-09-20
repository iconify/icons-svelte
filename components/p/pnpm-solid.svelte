<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd3tncc0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pd3tncc0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:pnpm-solid" {...props}></Icon>
