<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5257yb9v.css';
import '../../css/w/wgc4b7bwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="j5257yb9v"/><path class="wgc4b7bwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:accessibility" {...props}></Icon>
