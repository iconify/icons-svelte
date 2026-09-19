<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in43hzbnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":438,"height":512};
const content = `<path class="in43hzbnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:doxygen" {...props}></Icon>
