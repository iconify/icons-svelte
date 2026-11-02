<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjp3xsbsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hjp3xsbsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hand-helping-line" {...props}></Icon>
