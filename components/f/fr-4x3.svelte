<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmyfv_bvg.css';
import '../../css/o/o9ffdfb9u.css';
import '../../css/w/wgqpd53tm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<path class="vmyfv_bvg"/><path class="o9ffdfb9u"/><path class="wgqpd53tm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:fr-4x3" {...props}></Icon>
