<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/is7he1yqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="is7he1yqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:draggable-horizontal" {...props}></Icon>
