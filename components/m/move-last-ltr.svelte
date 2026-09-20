<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlnc2n5di.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qlnc2n5di"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:move-last-ltr" {...props}></Icon>
