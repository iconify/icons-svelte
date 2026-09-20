<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzcnnhbdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rzcnnhbdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:help-ltr" {...props}></Icon>
