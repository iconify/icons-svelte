<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mi0h6hbuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mi0h6hbuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:classify-line" {...props}></Icon>
