<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gsja-j37j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gsja-j37j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:hotel-gloss" {...props}></Icon>
