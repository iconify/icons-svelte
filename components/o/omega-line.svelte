<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr6-gac2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wr6-gac2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:omega-line" {...props}></Icon>
