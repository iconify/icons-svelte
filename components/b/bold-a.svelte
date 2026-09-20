<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohkm-6bju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ohkm-6bju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:bold-a" {...props}></Icon>
