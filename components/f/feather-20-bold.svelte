<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1rxiyxan.css';
import '../../css/b/b0cpgnbfh.css';
import '../../css/j/jl8htv4va.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w1rxiyxan"/><path class="b0cpgnbfh"/><path class="jl8htv4va"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:feather-20-bold" {...props}></Icon>
