<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zf-m5_bmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="zf-m5_bmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:hourglass" {...props}></Icon>
