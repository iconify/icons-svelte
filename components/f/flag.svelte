<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwbbifb6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vwbbifb6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:flag" {...props}></Icon>
