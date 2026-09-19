<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxq7scbii.css';
import '../../css/v/v2qz0z9zp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sxq7scbii"/><path class="v2qz0z9zp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-file-jpg" {...props}></Icon>
