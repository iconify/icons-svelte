<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogl56j_pb.css';
import '../../css/d/ddop6km7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ogl56j_pb"/><path class="ddop6km7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteocons:code-red" {...props}></Icon>
