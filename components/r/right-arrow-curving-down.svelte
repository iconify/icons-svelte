<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swkylxb0c.css';
import '../../css/x/xnoj2lhrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="swkylxb0c"/><path class="xnoj2lhrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:right-arrow-curving-down" {...props}></Icon>
