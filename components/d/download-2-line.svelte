<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf0rr5b1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mf0rr5b1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:download-2-line" {...props}></Icon>
