<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcb2sab0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mcb2sab0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:remote-line" {...props}></Icon>
