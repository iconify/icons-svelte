<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr6-vqfij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pr6-vqfij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:mouse-pointer-2" {...props}></Icon>
