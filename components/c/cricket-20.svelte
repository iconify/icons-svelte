<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkayohb4a.css';
import '../../css/n/n76vy6bdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rkayohb4a"/><path class="n76vy6bdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cricket-20" {...props}></Icon>
