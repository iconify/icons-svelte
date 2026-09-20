<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf1wgwbvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yf1wgwbvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bag-heart-filled" {...props}></Icon>
