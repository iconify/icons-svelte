<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbd9-edzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1920,"height":1600};
const content = `<path class="bbd9-edzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:gantt-o" {...props}></Icon>
