<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntt-te-ig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ntt-te-ig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-truck" {...props}></Icon>
