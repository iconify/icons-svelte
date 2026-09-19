<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3-lr-62j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i3-lr-62j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-file-plus" {...props}></Icon>
