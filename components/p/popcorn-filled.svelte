<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epsxxyetc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="epsxxyetc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:popcorn-filled" {...props}></Icon>
