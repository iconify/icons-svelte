<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wa3so01so.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wa3so01so"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:camera" {...props}></Icon>
