<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpwtmbbva.css';
import '../../css/w/w3w4p5b0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vpwtmbbva"/><path clip-rule="evenodd" class="w3w4p5b0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ordi" {...props}></Icon>
