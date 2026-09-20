<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rp7-oxbdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rp7-oxbdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:delta" {...props}></Icon>
