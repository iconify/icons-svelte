<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0mt_8qgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n0mt_8qgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-man-afro-gloss" {...props}></Icon>
