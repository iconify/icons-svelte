<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wk57u1bly.css';
import '../../css/x/x2gu2vr4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wk57u1bly"/><path class="x2gu2vr4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:paint-roll" {...props}></Icon>
