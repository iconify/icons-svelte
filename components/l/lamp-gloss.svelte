<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf575ubcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sf575ubcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:lamp-gloss" {...props}></Icon>
