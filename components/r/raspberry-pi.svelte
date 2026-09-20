<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr960vbov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wr960vbov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:raspberry-pi" {...props}></Icon>
