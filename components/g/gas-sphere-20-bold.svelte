<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_1gyeb8r.css';
import '../../css/c/ct6m-lb4p.css';
import '../../css/y/yfoxxnbix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b_1gyeb8r"/><path class="ct6m-lb4p"/><path class="yfoxxnbix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gas-sphere-20-bold" {...props}></Icon>
