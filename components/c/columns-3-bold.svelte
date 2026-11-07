<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4rs5k0ap.css';
import '../../css/d/dan73zqnv.css';
import '../../css/z/z41gnwbsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y4rs5k0ap"/><path class="dan73zqnv"/><path class="z41gnwbsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:columns-3-bold" {...props}></Icon>
