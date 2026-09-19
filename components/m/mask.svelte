<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzou1z3xk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pzou1z3xk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:mask" {...props}></Icon>
