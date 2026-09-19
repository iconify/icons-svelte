<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stsj2rbfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="stsj2rbfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-direction-right" {...props}></Icon>
