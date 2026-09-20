<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdylx-b6p.css';
import '../../css/s/skx7sybde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jdylx-b6p"/><path class="skx7sybde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:image-add-rtl" {...props}></Icon>
