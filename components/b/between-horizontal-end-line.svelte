<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wk121vbgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wk121vbgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:between-horizontal-end-line" {...props}></Icon>
