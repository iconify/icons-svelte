<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v20uhpbwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="v20uhpbwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:percent" {...props}></Icon>
