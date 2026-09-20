<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rp2g-og5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rp2g-og5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:peach-filled" {...props}></Icon>
