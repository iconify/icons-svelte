<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/defz0cbcm.css';
import '../../css/p/p4l2bobkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="defz0cbcm"/><path class="p4l2bobkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:id-card-48-bold" {...props}></Icon>
