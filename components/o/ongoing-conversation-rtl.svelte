<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbe0iemxf.css';
import '../../css/t/tiglpdb9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hbe0iemxf"/><path class="tiglpdb9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:ongoing-conversation-rtl" {...props}></Icon>
