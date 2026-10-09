<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdw4w6evj.css';
import '../../css/x/xn1pz4iuf.css';
import '../../css/w/w9gsb7blj.css';
import '../../css/h/h1e1mnb1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jdw4w6evj"/><path class="xn1pz4iuf"/><path class="w9gsb7blj"/><path class="h1e1mnb1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:clover-20-bold" {...props}></Icon>
