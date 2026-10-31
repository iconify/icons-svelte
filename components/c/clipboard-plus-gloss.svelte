<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uz3sw2bhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uz3sw2bhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:clipboard-plus-gloss" {...props}></Icon>
