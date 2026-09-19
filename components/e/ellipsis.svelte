<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zymh_bb2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="zymh_bb2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:ellipsis" {...props}></Icon>
