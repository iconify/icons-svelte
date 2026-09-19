<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d09b06_ir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d09b06_ir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:hat" {...props}></Icon>
