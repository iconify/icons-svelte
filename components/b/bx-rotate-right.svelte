<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xg4mjnb-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xg4mjnb-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-rotate-right" {...props}></Icon>
