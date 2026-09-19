<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ye5j1p-tl.css';
import '../../css/c/ca8-a7btp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ye5j1p-tl"/><path class="ca8-a7btp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:rename" {...props}></Icon>
