<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbp_debio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wbp_debio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:inspect-line" {...props}></Icon>
