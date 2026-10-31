<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oiow7sb-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oiow7sb-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bed-gloss" {...props}></Icon>
