<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srs9hjd-l.css';
import '../../css/c/cg8wilbxu.css';
import '../../css/p/p4vjspaxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<circle class="srs9hjd-l"/><path class="cg8wilbxu"/><path class="p4vjspaxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:hand-with-index-finger-and-thumb-crossed" {...props}></Icon>
