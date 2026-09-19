<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lp56aqbon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="lp56aqbon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:plug" {...props}></Icon>
