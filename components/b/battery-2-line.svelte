<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm3pn2bvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qm3pn2bvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:battery-2-line" {...props}></Icon>
