<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1k4k4b0q.css';
import '../../css/b/bdgm4mbrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="e1k4k4b0q"/><path class="bdgm4mbrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:hourglass-twotone" {...props}></Icon>
