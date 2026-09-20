<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0p2aabxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n0p2aabxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:moon3-filled" {...props}></Icon>
