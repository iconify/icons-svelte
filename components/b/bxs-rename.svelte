<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxv-nrbxk.css';
import '../../css/e/e03sdjqcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gxv-nrbxk"/><path class="e03sdjqcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-rename" {...props}></Icon>
