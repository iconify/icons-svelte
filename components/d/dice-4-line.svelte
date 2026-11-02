<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpjio5o_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mpjio5o_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dice-4-line" {...props}></Icon>
