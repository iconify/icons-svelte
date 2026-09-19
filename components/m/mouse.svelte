<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x55m2-bxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x55m2-bxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:mouse" {...props}></Icon>
