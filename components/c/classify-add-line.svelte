<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ielcc5-zr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ielcc5-zr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:classify-add-line" {...props}></Icon>
