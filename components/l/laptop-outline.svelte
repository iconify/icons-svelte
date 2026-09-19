<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxciqpbda.css';
import '../../css/f/fne6a9bsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="zxciqpbda"/><path class="fne6a9bsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:laptop-outline" {...props}></Icon>
