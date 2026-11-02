<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wa9uavbmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wa9uavbmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:more-3-line" {...props}></Icon>
