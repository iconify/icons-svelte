<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewjnt-fjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ewjnt-fjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:bold-armn-to" {...props}></Icon>
