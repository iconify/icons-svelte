<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgvbnbcfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mgvbnbcfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:plus-circle-gloss" {...props}></Icon>
