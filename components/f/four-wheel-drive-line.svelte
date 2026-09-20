<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3g7_wbvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3g7_wbvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:four-wheel-drive-line" {...props}></Icon>
