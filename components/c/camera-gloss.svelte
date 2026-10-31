<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obiis19rx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="obiis19rx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:camera-gloss" {...props}></Icon>
