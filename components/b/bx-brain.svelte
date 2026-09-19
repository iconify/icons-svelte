<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx2rbtbmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jx2rbtbmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-brain" {...props}></Icon>
