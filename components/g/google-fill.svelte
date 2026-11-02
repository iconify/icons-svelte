<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bijs8_3je.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bijs8_3je"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:google-fill" {...props}></Icon>
