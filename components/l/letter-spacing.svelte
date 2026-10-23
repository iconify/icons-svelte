<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7sif1blt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o7sif1blt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:letter-spacing" {...props}></Icon>
