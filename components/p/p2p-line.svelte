<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9tupkb2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l9tupkb2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:p2p-line" {...props}></Icon>
