<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aav7v0ikn.css';
import '../../css/q/q590whb4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="aav7v0ikn"/><path class="q590whb4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:playlist-20-bold" {...props}></Icon>
