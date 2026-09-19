<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xa-t1nyfw.css';
import '../../css/z/zjegb3bxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="xa-t1nyfw"/><path class="zjegb3bxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:building-stroke-12" {...props}></Icon>
