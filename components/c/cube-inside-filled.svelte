<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cnj__kbmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b cnj__kbmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cube-inside-filled" {...props}></Icon>
