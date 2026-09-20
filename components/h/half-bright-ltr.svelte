<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5x84ccwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k5x84ccwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:half-bright-ltr" {...props}></Icon>
