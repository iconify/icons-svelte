<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsjk3zbke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lsjk3zbke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:level-one-ltr" {...props}></Icon>
