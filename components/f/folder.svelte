<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sow8xugzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sow8xugzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:folder" {...props}></Icon>
