<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcv1sbczx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lcv1sbczx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:bold-f" {...props}></Icon>
