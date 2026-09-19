<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wq5ecs8zq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wq5ecs8zq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:airplane-mode" {...props}></Icon>
