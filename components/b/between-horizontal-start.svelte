<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvrr47wbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hvrr47wbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:between-horizontal-start" {...props}></Icon>
