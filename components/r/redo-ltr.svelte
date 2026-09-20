<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpwszlu2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rpwszlu2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:redo-ltr" {...props}></Icon>
