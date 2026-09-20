<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4e5dcc-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o4e5dcc-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:bold-arab-ain" {...props}></Icon>
