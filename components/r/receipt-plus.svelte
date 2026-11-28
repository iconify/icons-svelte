<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xucjgnbzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xucjgnbzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:receipt-plus" {...props}></Icon>
