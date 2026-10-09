<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vptd66bam.css';
import '../../css/x/x88lagbcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vptd66bam"/><path class="x88lagbcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:air-conditioner-20" {...props}></Icon>
