<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_qkk_bgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r_qkk_bgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:camera" {...props}></Icon>
