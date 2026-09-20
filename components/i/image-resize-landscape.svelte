<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct4c3sv7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ct4c3sv7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:image-resize-landscape" {...props}></Icon>
