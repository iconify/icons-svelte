<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a420hzb7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a420hzb7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:browser-ltr" {...props}></Icon>
