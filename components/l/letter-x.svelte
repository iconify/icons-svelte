<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttfi1kb_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ttfi1kb_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:letter-x" {...props}></Icon>
