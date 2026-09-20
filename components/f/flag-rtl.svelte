<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vt3prvmif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vt3prvmif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:flag-rtl" {...props}></Icon>
