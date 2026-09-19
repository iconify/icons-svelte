<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdkmxgblk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vdkmxgblk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-photo-album" {...props}></Icon>
