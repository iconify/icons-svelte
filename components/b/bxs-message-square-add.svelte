<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2_56yblu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z2_56yblu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-message-square-add" {...props}></Icon>
