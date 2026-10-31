<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_qlrgyny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r_qlrgyny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:helicopter-gloss" {...props}></Icon>
