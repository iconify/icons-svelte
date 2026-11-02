<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_4_h7yce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w_4_h7yce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-check-line" {...props}></Icon>
