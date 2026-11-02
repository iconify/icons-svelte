<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti_d_mbqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ti_d_mbqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pickax-line" {...props}></Icon>
