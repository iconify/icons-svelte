<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vs2agm2zp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vs2agm2zp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:previous-rtl" {...props}></Icon>
