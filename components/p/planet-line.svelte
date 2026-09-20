<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xc7hs2bbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xc7hs2bbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:planet-line" {...props}></Icon>
