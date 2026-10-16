<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2jl4nb0t.css';
import '../../css/z/zikzdnbwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c2jl4nb0t"/><path class="zikzdnbwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:brine-pond-20" {...props}></Icon>
