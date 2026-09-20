<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpcbw_w9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qpcbw_w9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:link-2-fill" {...props}></Icon>
