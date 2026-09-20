<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqy99db8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="iqy99db8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:help-rtl" {...props}></Icon>
