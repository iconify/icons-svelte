<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1v0ij09t.css';
import '../../css/c/cv6p3wbsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p1v0ij09t"/><path class="cv6p3wbsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:handshake-48" {...props}></Icon>
