<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyk6g0bcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qyk6g0bcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flexibility-fill" {...props}></Icon>
