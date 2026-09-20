<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrpbwjbpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="lrpbwjbpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:battery-full" {...props}></Icon>
