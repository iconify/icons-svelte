<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5ji-z8yd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k5ji-z8yd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:hand-peace" {...props}></Icon>
