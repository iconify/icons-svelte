<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvgij0b_x.css';
import '../../css/w/w0ntu2ieo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xvgij0b_x"/><path class="w0ntu2ieo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:menu-dots-circle-16" {...props}></Icon>
