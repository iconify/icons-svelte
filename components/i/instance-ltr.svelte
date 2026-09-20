<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onpq72bfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="onpq72bfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:instance-ltr" {...props}></Icon>
