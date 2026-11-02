<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3_ta5b5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m3_ta5b5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:radar-fill" {...props}></Icon>
