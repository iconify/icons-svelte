<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_opemo2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="o_opemo2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:comments" {...props}></Icon>
