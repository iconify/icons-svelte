<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mso5wcbws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mso5wcbws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:copy-rtl" {...props}></Icon>
