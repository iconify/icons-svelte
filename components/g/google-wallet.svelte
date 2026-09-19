<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvmop950l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rvmop950l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:google-wallet" {...props}></Icon>
