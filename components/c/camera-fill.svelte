<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sc5r50bnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sc5r50bnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:camera-fill" {...props}></Icon>
