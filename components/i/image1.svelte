<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rueir2m3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rueir2m3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:image1" {...props}></Icon>
