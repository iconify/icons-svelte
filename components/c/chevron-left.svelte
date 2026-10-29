<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjpkx0bhs.css';
import '../../css/f/fh4wf_0gy.css';
import '../../css/r/r4u87jbxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-shadow zjpkx0bhs"/><path class="fh4wf_0gy wm-k"/><path class="r4u87jbxf wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-pastel:chevron-left" {...props}></Icon>
