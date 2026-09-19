<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw36nxb_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zw36nxb_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:link-outline" {...props}></Icon>
