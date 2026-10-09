<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofts-6g4o.css';
import '../../css/g/goolytbaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ofts-6g4o"/><path class="goolytbaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:panel-bottom-20" {...props}></Icon>
