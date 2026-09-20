<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1p8q7b1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m1p8q7b1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:download-2-fill" {...props}></Icon>
