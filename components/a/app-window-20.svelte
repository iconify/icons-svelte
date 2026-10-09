<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofts-6g4o.css';
import '../../css/o/okfht2vmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ofts-6g4o"/><path class="okfht2vmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:app-window-20" {...props}></Icon>
