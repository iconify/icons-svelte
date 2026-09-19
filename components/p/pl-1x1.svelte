<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/d/de5y7ab3j.css';
import '../../css/y/yhd-geb2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<g class="d2kvgvbvc"><path class="de5y7ab3j"/><path class="yhd-geb2e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:pl-1x1" {...props}></Icon>
