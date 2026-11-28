<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xoaf3-v2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xoaf3-v2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:accessibility" {...props}></Icon>
