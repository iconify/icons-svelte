<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8jdxt_7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="x8jdxt_7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:closed-captioning" {...props}></Icon>
